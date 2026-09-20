<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyq4nf5rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyq4nf5rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:libreoffice-math" {...props}></Icon>
