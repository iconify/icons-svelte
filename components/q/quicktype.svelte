<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is6dcfmkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is6dcfmkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quicktype" {...props}></Icon>
