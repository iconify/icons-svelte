<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efu0u547c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efu0u547c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:delete-alt" {...props}></Icon>
