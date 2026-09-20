<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1okqdbgr.css';
import '../../css/b/bq-mafblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1okqdbgr"/><path clip-rule="evenodd" class="bq-mafblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hedera-hashgraph" {...props}></Icon>
