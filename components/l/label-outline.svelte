<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp7enpb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp7enpb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:label-outline" {...props}></Icon>
