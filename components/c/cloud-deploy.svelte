<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_4ht5bkm.css';
import '../../css/q/q2dc-8bor.css';
import '../../css/b/b0jxrubul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_4ht5bkm"/><path class="q2dc-8bor"/><path class="b0jxrubul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-deploy" {...props}></Icon>
