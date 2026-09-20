<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrokq9bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrokq9bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:forgejo" {...props}></Icon>
