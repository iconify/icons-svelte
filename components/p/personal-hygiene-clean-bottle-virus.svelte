<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzc8en32u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzc8en32u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:personal-hygiene-clean-bottle-virus" {...props}></Icon>
