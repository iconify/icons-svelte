<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqk2l_13t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqk2l_13t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:octagon-fill" {...props}></Icon>
