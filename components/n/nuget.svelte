<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uow25q6ka.css';
import '../../css/i/iyj96ne-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="uow25q6ka"/><path class="iyj96ne-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nuget" {...props}></Icon>
