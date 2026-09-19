<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvyz_x15a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvyz_x15a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:h2-solid" {...props}></Icon>
