<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtpw-r91t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtpw-r91t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock-alt-02" {...props}></Icon>
