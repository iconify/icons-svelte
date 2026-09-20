<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpb8lgbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpb8lgbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-or-many-to-many" {...props}></Icon>
