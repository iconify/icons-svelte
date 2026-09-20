<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcmfmdbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcmfmdbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hdfc-bank" {...props}></Icon>
