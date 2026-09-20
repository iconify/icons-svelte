<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emcy89btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emcy89btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:realm" {...props}></Icon>
