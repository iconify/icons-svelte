<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn16o9_6z.css';
import '../../css/j/jsf9fd5pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn16o9_6z"/><path clip-rule="evenodd" class="jsf9fd5pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bike" {...props}></Icon>
