<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkzge6j-e.css';
import '../../css/j/jd1l75b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkzge6j-e"/><path class="jd1l75b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-square-2-bold" {...props}></Icon>
