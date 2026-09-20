<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjiz8hbrl.css';
import '../../css/e/eox5sonav.css';
import '../../css/v/v4i2ew1ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjiz8hbrl"/><circle class="eox5sonav"/><circle class="v4i2ew1ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:insta-duotone" {...props}></Icon>
