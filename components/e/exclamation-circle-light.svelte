<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_ma8083f.css';
import '../../css/v/v9y5wi_ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_ma8083f"/><path class="v9y5wi_ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-circle-light" {...props}></Icon>
