<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8d-vlniz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8d-vlniz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:database-fill" {...props}></Icon>
