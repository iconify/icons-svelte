<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beoipcbng.css';
import '../../css/t/tba9ohb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beoipcbng"/><path class="tba9ohb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:credit-card-duotone" {...props}></Icon>
