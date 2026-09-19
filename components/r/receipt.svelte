<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tosj05bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tosj05bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:receipt" {...props}></Icon>
