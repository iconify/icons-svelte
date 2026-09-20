<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-kjzsbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="v-kjzsbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:arrow-up" {...props}></Icon>
