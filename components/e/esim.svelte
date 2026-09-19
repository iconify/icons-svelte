<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sso_qpbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sso_qpbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:esim" {...props}></Icon>
