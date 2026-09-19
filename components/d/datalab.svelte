<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3x112bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x112bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:datalab" {...props}></Icon>
