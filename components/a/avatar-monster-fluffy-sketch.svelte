<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h44oajipe.css';
import '../../css/e/ezdj7qokr.css';
import '../../css/a/a__iqxtux.css';
import '../../css/m/mxgtmybcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h44oajipe"/><path class="ezdj7qokr wm-k"/><path class="a__iqxtux wm-k"/><path class="mxgtmybcd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-monster-fluffy-sketch" {...props}></Icon>
