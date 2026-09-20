<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tp7w9wbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-ty" {...props}></Icon>
<style>
:global(.tp7w9wbsw) {
  fill: var(--svg-color--46ebe1, #46ebe1);
  d: path("M30 6.48H18.24V2h-14v4.48H2v10.64h2.24v8.34c0 2.5 2.03 4.54 4.54 4.54H30V19.36H18.24v-2.24h7.22c2.5 0 4.54-2.03 4.54-4.54z");
}

</style>
