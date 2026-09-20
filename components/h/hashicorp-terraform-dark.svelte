<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-d3ovb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-d3ovb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-terraform-dark" {...props}></Icon>
