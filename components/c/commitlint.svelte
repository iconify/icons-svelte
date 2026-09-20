<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgfakv3lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgfakv3lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:commitlint" {...props}></Icon>
