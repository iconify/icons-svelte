<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z06ze1bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z06ze1bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:meta" {...props}></Icon>
