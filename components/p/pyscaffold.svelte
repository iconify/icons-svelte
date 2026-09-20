<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2zwanb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2zwanb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pyscaffold" {...props}></Icon>
