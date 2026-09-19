<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k74xvhbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k74xvhbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:moon" {...props}></Icon>
