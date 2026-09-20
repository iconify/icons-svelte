<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsegj49pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsegj49pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pdm" {...props}></Icon>
