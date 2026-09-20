<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egq4ghbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egq4ghbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cardano" {...props}></Icon>
