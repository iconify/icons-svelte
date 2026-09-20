<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofqds83lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofqds83lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:php-cs-fixer" {...props}></Icon>
