<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn7088dpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dn7088dpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calculator3-filled" {...props}></Icon>
