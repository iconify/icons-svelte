<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcn2q1bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcn2q1bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:migrate-for-anthos" {...props}></Icon>
