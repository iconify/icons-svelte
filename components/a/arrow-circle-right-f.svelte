<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo2u5rbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="bo2u5rbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-right-f" {...props}></Icon>
