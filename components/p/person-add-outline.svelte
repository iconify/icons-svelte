<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdnb1nb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdnb1nb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-add-outline" {...props}></Icon>
