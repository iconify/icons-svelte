<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob2rwxbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob2rwxbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:diamond-stone" {...props}></Icon>
