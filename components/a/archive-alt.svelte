<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwbnv2j0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwbnv2j0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:archive-alt" {...props}></Icon>
