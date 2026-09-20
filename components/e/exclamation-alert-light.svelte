<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl82r-bam.css';
import '../../css/v/v9y5wi_ot.css';
import '../../css/q/q_ma8083f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl82r-bam"/><path class="v9y5wi_ot"/><path class="q_ma8083f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-alert-light" {...props}></Icon>
