<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmh5macky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmh5macky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:babel" {...props}></Icon>
