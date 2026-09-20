<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2sascbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2sascbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-open-sharp-fill" {...props}></Icon>
