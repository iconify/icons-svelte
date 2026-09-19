<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-eim3bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-eim3bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:circle" {...props}></Icon>
