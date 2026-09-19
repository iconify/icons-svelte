<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4kg3hb2u.css';
import '../../css/x/x_tu0ab7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4kg3hb2u"/><path class="x_tu0ab7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:content-lifecycle-management" {...props}></Icon>
