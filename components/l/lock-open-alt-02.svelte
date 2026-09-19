<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff8g36beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff8g36beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock-open-alt-02" {...props}></Icon>
