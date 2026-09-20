<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-b-5jban.css';
import '../../css/q/q9k8bmnxn.css';
import '../../css/b/bpphhjblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-b-5jban"/><path class="q9k8bmnxn"/><path class="bpphhjblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:knife-fork-1" {...props}></Icon>
