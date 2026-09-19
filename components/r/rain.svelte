<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvf5nbbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvf5nbbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rain" {...props}></Icon>
