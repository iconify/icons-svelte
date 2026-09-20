<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq0l3cvad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq0l3cvad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-edit-outline" {...props}></Icon>
