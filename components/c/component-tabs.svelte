<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_uj--bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_uj--bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-tabs" {...props}></Icon>
