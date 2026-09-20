<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlz2ze66a.css';
import '../../css/n/n4hz257hz.css';
import '../../css/z/zktgoabmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlz2ze66a"/><path clip-rule="evenodd" class="n4hz257hz"/><path class="zktgoabmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mft" {...props}></Icon>
