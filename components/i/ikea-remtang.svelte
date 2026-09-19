<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qya3aihwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qya3aihwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-remtang" {...props}></Icon>
