<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3sibft6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3sibft6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phone-forwarded-solid" {...props}></Icon>
