<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5dx6nelf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5dx6nelf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:adore" {...props}></Icon>
