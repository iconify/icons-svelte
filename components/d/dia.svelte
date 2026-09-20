<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ilb8yfl.css';
import '../../css/h/hjk7fac9x.css';
import '../../css/s/shoq0tb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ilb8yfl"/><path class="hjk7fac9x"/><path class="shoq0tb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dia" {...props}></Icon>
