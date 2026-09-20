<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9mdc-bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9mdc-bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive2" {...props}></Icon>
