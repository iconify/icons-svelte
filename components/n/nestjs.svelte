<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4j1qob0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4j1qob0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nestjs" {...props}></Icon>
