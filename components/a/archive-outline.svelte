<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiz8lpbui.css';
import '../../css/i/iufc13bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiz8lpbui"/><rect class="iufc13bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:archive-outline" {...props}></Icon>
