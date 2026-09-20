<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub0hiubzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ub0hiubzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:documents-minimalistic-outline" {...props}></Icon>
