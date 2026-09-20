<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8wwe7b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8wwe7b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mlflow" {...props}></Icon>
