<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr_4lkqsn.css';
import '../../css/k/kwj8pfbpn.css';
import '../../css/x/xqzgogbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr_4lkqsn"/><path class="kwj8pfbpn"/><path class="xqzgogbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:flip-v-alt" {...props}></Icon>
