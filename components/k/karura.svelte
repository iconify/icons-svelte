<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbdndxbzu.css';
import '../../css/h/h892u3ajl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbdndxbzu"/><path class="h892u3ajl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:karura" {...props}></Icon>
