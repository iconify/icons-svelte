<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql9ho9wwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ql9ho9wwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:collapse-outline" {...props}></Icon>
