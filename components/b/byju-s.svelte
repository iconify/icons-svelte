<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbf384hqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbf384hqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:byju-s" {...props}></Icon>
