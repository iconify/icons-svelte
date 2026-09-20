<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b09m9nbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b09m9nbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:laravel" {...props}></Icon>
