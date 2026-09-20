<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8-usu87f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8-usu87f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bracket-curly" {...props}></Icon>
