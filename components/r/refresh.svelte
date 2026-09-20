<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4i2ew1ke.css';
import '../../css/m/m8lmgdacv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path class="m8lmgdacv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:refresh" {...props}></Icon>
