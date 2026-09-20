<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7su_645o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="u7su_645o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-circle-up-right-f" {...props}></Icon>
