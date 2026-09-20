<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngzxm-lii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngzxm-lii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dizzy-meh" {...props}></Icon>
