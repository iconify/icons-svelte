<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nozmsb7hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nozmsb7hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:preview" {...props}></Icon>
