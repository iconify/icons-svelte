<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk69bcc_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk69bcc_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cope" {...props}></Icon>
