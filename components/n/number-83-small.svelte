<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui_95wbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui_95wbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-83-small" {...props}></Icon>
