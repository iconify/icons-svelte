<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpf0o4buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpf0o4buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:repeat" {...props}></Icon>
