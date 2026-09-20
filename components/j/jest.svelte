<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhai-vmmb.css';
import '../../css/q/q3uobhc3c.css';
import '../../css/n/nd-_p_a3p.css';
import '../../css/v/v03hwspvx.css';
import '../../css/f/fzk14abag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lhai-vmmb"/><path class="q3uobhc3c"/><circle class="nd-_p_a3p"/><circle class="v03hwspvx"/><circle class="fzk14abag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:jest" {...props}></Icon>
