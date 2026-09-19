<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx33ejloy.css';
import '../../css/g/g4efp7-2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx33ejloy"/><path class="g4efp7-2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:heroku" {...props}></Icon>
