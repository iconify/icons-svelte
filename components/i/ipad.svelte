<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq_ba2bfa.css';
import '../../css/a/ahe_qiacf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="iq_ba2bfa"/><path clip-rule="evenodd" class="ahe_qiacf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:ipad" {...props}></Icon>
