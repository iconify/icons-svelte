<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq8p88zgp.css';
import '../../css/f/fxsw1ibsd.css';
import '../../css/y/ye66r86mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uq8p88zgp"/><path class="fxsw1ibsd"/><path class="ye66r86mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:delete-48" {...props}></Icon>
