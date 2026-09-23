<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epm1c_bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epm1c_bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:parentheses-sharp" {...props}></Icon>
