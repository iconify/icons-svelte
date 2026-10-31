<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfwl-6rai.css';
import '../../css/p/p-xswwuam.css';
import '../../css/v/vzm4z_6wm.css';
import '../../css/t/tkrh4u31z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jfwl-6rai"/><path class="p-xswwuam"/><path class="vzm4z_6wm"/><path class="tkrh4u31z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:beef" {...props}></Icon>
