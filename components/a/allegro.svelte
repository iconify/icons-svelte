<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toxf06xxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toxf06xxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:allegro" {...props}></Icon>
