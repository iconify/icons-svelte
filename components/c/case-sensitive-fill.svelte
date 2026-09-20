<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu5e9zo7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu5e9zo7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:case-sensitive-fill" {...props}></Icon>
