<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9igabbew.css';
import '../../css/w/wpb5j1boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer m9igabbew"/><path class="duoicon-primary-layer wpb5j1boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:book-3" {...props}></Icon>
