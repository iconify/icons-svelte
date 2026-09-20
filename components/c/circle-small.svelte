<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q26bobc_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="q26bobc_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:circle-small" {...props}></Icon>
