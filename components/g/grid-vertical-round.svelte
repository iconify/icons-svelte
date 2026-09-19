<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lij1qyb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lij1qyb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid-vertical-round" {...props}></Icon>
