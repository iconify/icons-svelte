<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piu2dnbsw.css';
import '../../css/q/qapg4nbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piu2dnbsw"/><path clip-rule="evenodd" class="qapg4nbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:png" {...props}></Icon>
