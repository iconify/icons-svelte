<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au2sf5mhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au2sf5mhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-femme" {...props}></Icon>
