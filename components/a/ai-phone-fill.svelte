<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku6a4achx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku6a4achx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-phone-fill" {...props}></Icon>
