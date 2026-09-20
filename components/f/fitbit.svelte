<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-4eq9bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-4eq9bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fitbit" {...props}></Icon>
