<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-eactb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-eactb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onlyoffice" {...props}></Icon>
