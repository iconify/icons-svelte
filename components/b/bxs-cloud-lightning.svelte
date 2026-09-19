<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_42c7mmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_42c7mmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cloud-lightning" {...props}></Icon>
