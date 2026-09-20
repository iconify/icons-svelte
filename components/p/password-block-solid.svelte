<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k28hr6b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k28hr6b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:password-block-solid" {...props}></Icon>
