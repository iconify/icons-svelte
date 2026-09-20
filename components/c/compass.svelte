<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcay3j-in.css';
import '../../css/s/seqwdcaye.css';
import '../../css/j/jmfazjblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcay3j-in"/><path class="seqwdcaye"/><path class="jmfazjblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:compass" {...props}></Icon>
