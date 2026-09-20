<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv0ihtbqe.css';
import '../../css/p/p06tfrbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gv0ihtbqe"/><path clip-rule="evenodd" class="p06tfrbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:contract-solid" {...props}></Icon>
