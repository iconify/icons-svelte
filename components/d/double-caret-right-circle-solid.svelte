<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg6jjtbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qg6jjtbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-right-circle-solid" {...props}></Icon>
