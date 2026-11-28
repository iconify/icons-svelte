<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms8a113pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms8a113pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pill-bottle" {...props}></Icon>
