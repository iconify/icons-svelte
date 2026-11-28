<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkfoqxbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkfoqxbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-detect-solid" {...props}></Icon>
