<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcx7mn54s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-2};
const content = `<path class="kcx7mn54s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:calculator" {...props}></Icon>
