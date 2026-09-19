<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohht1ebir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohht1ebir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:profile-fill" {...props}></Icon>
