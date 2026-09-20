<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eog_v_cug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eog_v_cug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:harmonyos" {...props}></Icon>
