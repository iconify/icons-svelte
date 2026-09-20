<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6oybf-di.css';
import '../../css/d/dh5g9c5ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z6oybf-di"/><path class="dh5g9c5ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bug" {...props}></Icon>
