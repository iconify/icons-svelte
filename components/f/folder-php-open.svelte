<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pan31eb4g.css';
import '../../css/j/jef3z0auc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pan31eb4g"/><path class="jef3z0auc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-php-open" {...props}></Icon>
