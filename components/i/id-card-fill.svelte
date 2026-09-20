<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct_lf2gmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct_lf2gmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:id-card-fill" {...props}></Icon>
